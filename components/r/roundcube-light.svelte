<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmbgd7baw.css';
import '../../css/k/kczhvw7ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmbgd7baw"/><path class="kczhvw7ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:roundcube-light" {...props}></Icon>
