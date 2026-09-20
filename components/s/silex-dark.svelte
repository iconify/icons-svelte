<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om9141zpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="om9141zpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:silex-dark" {...props}></Icon>
