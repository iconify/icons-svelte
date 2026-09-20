<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1gnk_b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1gnk_b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:server-cloud" {...props}></Icon>
