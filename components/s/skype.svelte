<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp90n_bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp90n_bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:skype" {...props}></Icon>
