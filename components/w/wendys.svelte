<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le0cgmbgy.css';
import '../../css/s/swqxefodk.css';
import '../../css/c/ci0zejzuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1230,"height":526};
const content = `<path class="le0cgmbgy"/><path class="swqxefodk"/><path class="ci0zejzuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wendys" {...props}></Icon>
