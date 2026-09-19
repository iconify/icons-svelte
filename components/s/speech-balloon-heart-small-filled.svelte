<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxqh5fbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lxqh5fbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speech-balloon-heart-small-filled" {...props}></Icon>
