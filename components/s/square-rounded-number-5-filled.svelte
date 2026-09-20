<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snv5_fs9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snv5_fs9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-number-5-filled" {...props}></Icon>
