<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya9b5bb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya9b5bb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:user-card-id" {...props}></Icon>
