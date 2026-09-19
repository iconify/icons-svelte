<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke2tg-bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ke2tg-bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni5475-box" {...props}></Icon>
