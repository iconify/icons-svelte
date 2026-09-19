<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyf9mq7mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vyf9mq7mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:wastebasket" {...props}></Icon>
