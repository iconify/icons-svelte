<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd9a8-uca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rd9a8-uca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:table-cells-merge-outline" {...props}></Icon>
