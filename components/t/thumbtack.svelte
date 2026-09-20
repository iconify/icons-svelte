<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as9pbrq8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="as9pbrq8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:thumbtack" {...props}></Icon>
