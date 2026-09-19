<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehara_hjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ehara_hjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:user-add" {...props}></Icon>
