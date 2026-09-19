<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4jmgynoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="j4jmgynoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-list-fill" {...props}></Icon>
