<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq24u9byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eq24u9byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wheelchair-remix" {...props}></Icon>
