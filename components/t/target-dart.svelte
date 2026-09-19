<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2rj0jbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z2rj0jbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:target-dart" {...props}></Icon>
