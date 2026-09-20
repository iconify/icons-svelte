<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaak9bouk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kaak9bouk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:subscript" {...props}></Icon>
