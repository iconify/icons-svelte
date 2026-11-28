<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmucpsbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmucpsbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:waves-arrow-down" {...props}></Icon>
