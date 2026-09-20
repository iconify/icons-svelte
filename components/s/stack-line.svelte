<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1ndc7yso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ndc7yso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stack-line" {...props}></Icon>
