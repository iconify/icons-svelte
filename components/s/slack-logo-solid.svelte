<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxtxpdbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mxtxpdbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:slack-logo-solid" {...props}></Icon>
