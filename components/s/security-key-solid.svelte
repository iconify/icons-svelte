<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onhx01o1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onhx01o1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:security-key-solid" {...props}></Icon>
