<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny_6rsfhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ny_6rsfhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:xbox-live-logo-solid" {...props}></Icon>
