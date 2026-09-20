<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjs5d_nch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjs5d_nch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:triangle-alert-sharp-fill" {...props}></Icon>
