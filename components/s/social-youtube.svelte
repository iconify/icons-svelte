<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v25ijb-ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v25ijb-ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-youtube" {...props}></Icon>
