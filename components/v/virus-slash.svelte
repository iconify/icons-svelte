<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nif2_eh7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nif2_eh7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:virus-slash" {...props}></Icon>
