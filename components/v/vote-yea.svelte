<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq4vmr3hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="eq4vmr3hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:vote-yea" {...props}></Icon>
