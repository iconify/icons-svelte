<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vprgaobhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vprgaobhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:whistle-16" {...props}></Icon>
