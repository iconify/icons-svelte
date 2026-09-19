<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kccz5db_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kccz5db_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tool-alt-filled" {...props}></Icon>
