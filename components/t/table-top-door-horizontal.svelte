<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swew10n1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="swew10n1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-door-horizontal" {...props}></Icon>
