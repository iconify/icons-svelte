<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8fpg0bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="h8fpg0bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sigma" {...props}></Icon>
