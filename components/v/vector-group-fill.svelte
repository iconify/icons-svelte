<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vshyk7bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vshyk7bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vector-group-fill" {...props}></Icon>
