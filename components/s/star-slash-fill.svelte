<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekjy-ml0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ekjy-ml0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:star-slash-fill" {...props}></Icon>
