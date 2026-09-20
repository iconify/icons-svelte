<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egkkoob5g.css';
import '../../css/o/ogb19tc_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="egkkoob5g"/><path class="ogb19tc_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storybook-dark" {...props}></Icon>
