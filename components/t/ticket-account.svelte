<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au22jrneh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au22jrneh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ticket-account" {...props}></Icon>
