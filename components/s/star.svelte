<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6cgcp9gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="b6cgcp9gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:star" {...props}></Icon>
