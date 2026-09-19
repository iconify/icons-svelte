<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqgumy6mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bqgumy6mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:table-badge-more-fill" {...props}></Icon>
