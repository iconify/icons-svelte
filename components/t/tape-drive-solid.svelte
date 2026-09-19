<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdr6idi7u.css';
import '../../css/r/rpykv1bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="sdr6idi7u"/><path class="rpykv1bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:tape-drive-solid" {...props}></Icon>
