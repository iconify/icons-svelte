<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd1pqpwnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cd1pqpwnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:windows-small" {...props}></Icon>
