<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_29im-_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e_29im-_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:storybook" {...props}></Icon>
