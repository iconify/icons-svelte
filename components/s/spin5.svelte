<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o27adk0py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="o27adk0py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:spin5" {...props}></Icon>
