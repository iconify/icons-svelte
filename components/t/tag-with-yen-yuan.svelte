<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dklxusbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dklxusbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tag-with-yen-yuan" {...props}></Icon>
