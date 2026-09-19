<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z43em6nnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z43em6nnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ski-dice-faces-01" {...props}></Icon>
