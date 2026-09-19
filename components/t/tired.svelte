<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh4sc5b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="lh4sc5b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:tired" {...props}></Icon>
