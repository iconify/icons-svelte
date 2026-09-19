<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au6wgzbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="au6wgzbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:thought-balloon" {...props}></Icon>
