<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dszobdc2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dszobdc2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:tb-24px" {...props}></Icon>
