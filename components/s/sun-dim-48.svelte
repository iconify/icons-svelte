<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neup3sbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="neup3sbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-dim-48" {...props}></Icon>
