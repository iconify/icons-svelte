<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-x5ajb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-x5ajb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stethoscope" {...props}></Icon>
