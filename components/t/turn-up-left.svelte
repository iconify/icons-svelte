<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvynadbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvynadbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:turn-up-left" {...props}></Icon>
