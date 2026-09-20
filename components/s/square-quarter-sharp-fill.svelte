<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_jr94bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_jr94bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-quarter-sharp-fill" {...props}></Icon>
