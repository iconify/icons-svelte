<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo89bj-np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zo89bj-np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:thumbs-down" {...props}></Icon>
