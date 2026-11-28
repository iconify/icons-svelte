<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxx_4tbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxx_4tbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stairs" {...props}></Icon>
