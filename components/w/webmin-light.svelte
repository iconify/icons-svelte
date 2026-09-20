<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to8eil6jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="to8eil6jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webmin-light" {...props}></Icon>
