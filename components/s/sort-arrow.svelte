<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuelntopd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuelntopd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sort-arrow" {...props}></Icon>
