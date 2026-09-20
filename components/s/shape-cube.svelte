<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpc-7dbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpc-7dbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shape-cube" {...props}></Icon>
