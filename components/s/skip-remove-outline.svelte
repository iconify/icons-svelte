<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6c7q-smu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6c7q-smu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip-remove-outline" {...props}></Icon>
