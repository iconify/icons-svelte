<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3-4ylime.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g3-4ylime"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:speaking-head" {...props}></Icon>
