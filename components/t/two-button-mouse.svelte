<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n75bgdbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n75bgdbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:two-button-mouse" {...props}></Icon>
