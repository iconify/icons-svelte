<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7nl5gbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k7nl5gbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:stethoscope-solid" {...props}></Icon>
