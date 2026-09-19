<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2yusd24j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o2yusd24j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:user-remove" {...props}></Icon>
