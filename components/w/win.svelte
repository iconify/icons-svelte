<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaw9wkbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qaw9wkbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:win" {...props}></Icon>
