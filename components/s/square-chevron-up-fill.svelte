<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu_9opbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu_9opbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevron-up-fill" {...props}></Icon>
