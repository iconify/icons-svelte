<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_jyd0s0l.css';
import '../../css/s/sk9-dtbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o_jyd0s0l"/><path clip-rule="evenodd" class="sk9-dtbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:success-32" {...props}></Icon>
