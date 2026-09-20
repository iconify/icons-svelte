<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsny7o2lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsny7o2lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:semantic-ui" {...props}></Icon>
