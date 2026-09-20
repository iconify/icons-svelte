<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0cxxdvdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="n0cxxdvdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:user-square-solid" {...props}></Icon>
