<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_2pc4bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_2pc4bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:typeorm" {...props}></Icon>
