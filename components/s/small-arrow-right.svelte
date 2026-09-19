<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_07bhb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":210,"height":700};
const content = `<path class="o_07bhb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:small-arrow-right" {...props}></Icon>
