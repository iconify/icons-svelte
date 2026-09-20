<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4oeq0bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j4oeq0bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:triangle-up" {...props}></Icon>
