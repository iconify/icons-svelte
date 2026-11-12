<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egkkoob5g.css';
import '../../css/m/m9rpzdbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="egkkoob5g"/><path class="m9rpzdbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storybook-dark" {...props}></Icon>
