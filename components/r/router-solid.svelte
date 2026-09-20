<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgha61bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kgha61bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:router-solid" {...props}></Icon>
