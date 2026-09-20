<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnf3jj1ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jnf3jj1ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:toml-16" {...props}></Icon>
