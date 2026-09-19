<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0216bb9l.css';
import '../../css/o/o_a2tub4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0216bb9l"/><path class="o_a2tub4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:trustpilot" {...props}></Icon>
