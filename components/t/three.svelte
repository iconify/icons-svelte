<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htpa-d4kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htpa-d4kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:three" {...props}></Icon>
