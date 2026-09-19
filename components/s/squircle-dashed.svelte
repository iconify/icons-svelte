<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmyumyv0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmyumyv0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:squircle-dashed" {...props}></Icon>
