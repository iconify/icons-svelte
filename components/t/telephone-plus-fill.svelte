<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivagqpbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ivagqpbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:telephone-plus-fill" {...props}></Icon>
