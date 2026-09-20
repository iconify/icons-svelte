<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhov7xoyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhov7xoyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:verified-badge-fill" {...props}></Icon>
