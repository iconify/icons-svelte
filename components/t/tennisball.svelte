<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tij9n_bhf.css';
import '../../css/e/ezspdub9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tij9n_bhf"/><path class="ezspdub9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tennisball" {...props}></Icon>
