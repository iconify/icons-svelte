<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufyq-fb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ufyq-fb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:watch" {...props}></Icon>
