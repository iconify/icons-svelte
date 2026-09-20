<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty8dq-_bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty8dq-_bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scales-line" {...props}></Icon>
