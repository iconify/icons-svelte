<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftmk4idvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ftmk4idvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:text-indent" {...props}></Icon>
