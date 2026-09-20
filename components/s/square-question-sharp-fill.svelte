<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs1lw6mbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gs1lw6mbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-question-sharp-fill" {...props}></Icon>
