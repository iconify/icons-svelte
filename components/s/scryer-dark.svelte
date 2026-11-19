<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo29c561l.css';
import '../../css/i/iaayajjtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wo29c561l"/><path class="iaayajjtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scryer-dark" {...props}></Icon>
