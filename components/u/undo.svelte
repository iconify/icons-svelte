<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbgp3bhag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgp3bhag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:undo" {...props}></Icon>
