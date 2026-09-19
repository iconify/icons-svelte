<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbd9vjcah.css';
import '../../css/o/o559_525r.css';
import '../../css/c/cn051wbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbd9vjcah"/><path class="o559_525r"/><path class="cn051wbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:thumbs-down-sharp" {...props}></Icon>
