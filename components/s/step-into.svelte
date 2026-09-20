<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y10tf2bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y10tf2bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:step-into" {...props}></Icon>
