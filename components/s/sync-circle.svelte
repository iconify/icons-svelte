<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9vtffbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k9vtffbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:sync-circle" {...props}></Icon>
