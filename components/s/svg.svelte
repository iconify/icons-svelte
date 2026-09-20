<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3s_77bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3s_77bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:svg" {...props}></Icon>
