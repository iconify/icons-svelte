<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnovpgzed.css';
import '../../css/j/jikoplbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tnovpgzed"/><path clip-rule="evenodd" class="jikoplbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ungroup-16" {...props}></Icon>
