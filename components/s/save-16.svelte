<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb65qtbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tb65qtbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:save-16" {...props}></Icon>
