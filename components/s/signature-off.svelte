<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skew6abkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skew6abkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:signature-off" {...props}></Icon>
