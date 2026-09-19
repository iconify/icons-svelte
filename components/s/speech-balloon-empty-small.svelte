<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ergqbgbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ergqbgbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speech-balloon-empty-small" {...props}></Icon>
