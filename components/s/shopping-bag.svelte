<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn-dbnw6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xn-dbnw6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:shopping-bag" {...props}></Icon>
