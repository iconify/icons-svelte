<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2nr5ifks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2nr5ifks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip-previous-circle-outline" {...props}></Icon>
