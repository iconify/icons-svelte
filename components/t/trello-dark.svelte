<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id4sdkj0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="id4sdkj0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trello-dark" {...props}></Icon>
