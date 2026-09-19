<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o05-ijw2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o05-ijw2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:text-rotate-90-degrees" {...props}></Icon>
