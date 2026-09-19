<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuoe7pgag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="vuoe7pgag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:spin1" {...props}></Icon>
