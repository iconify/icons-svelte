<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw0upqbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qw0upqbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ticket" {...props}></Icon>
