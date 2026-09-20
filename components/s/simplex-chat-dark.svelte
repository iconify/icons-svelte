<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu-wovbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bu-wovbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:simplex-chat-dark" {...props}></Icon>
