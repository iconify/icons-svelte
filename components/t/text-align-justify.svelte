<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dezus5bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dezus5bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:text-align-justify" {...props}></Icon>
