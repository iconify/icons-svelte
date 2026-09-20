<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfmjwqt-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfmjwqt-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:slash" {...props}></Icon>
