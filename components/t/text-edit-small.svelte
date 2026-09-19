<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlrbs6dvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zlrbs6dvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:text-edit-small" {...props}></Icon>
