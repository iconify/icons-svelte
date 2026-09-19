<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_4ecru_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x_4ecru_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:trash-slash-fill" {...props}></Icon>
