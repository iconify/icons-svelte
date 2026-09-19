<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o72q58bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o72q58bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:trash2-fill" {...props}></Icon>
