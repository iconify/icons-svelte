<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8_jvyq7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t8_jvyq7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:table-cells-merge-20-solid" {...props}></Icon>
