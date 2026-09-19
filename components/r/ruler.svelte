<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3yi-jbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3yi-jbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:ruler" {...props}></Icon>
