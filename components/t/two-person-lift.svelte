<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icsbmobje.css';
import '../../css/b/bweidcb3i.css';
import '../../css/f/fktdbrb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="icsbmobje"/><path class="bweidcb3i"/><path class="fktdbrb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:two-person-lift" {...props}></Icon>
