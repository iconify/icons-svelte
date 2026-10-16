<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jya9pfbcj.css';
import '../../css/d/d_8ujsb3y.css';
import '../../css/c/c65-ehvfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jya9pfbcj"/><path class="d_8ujsb3y"/><path class="c65-ehvfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:suction-bucket-48" {...props}></Icon>
