<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp4uul4lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="bp4uul4lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tennis" {...props}></Icon>
