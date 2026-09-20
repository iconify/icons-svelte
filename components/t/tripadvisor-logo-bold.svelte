<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_8bqzb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_8bqzb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:tripadvisor-logo-bold" {...props}></Icon>
