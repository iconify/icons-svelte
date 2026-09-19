<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx20rqbza.css';
import '../../css/m/m94p08b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx20rqbza"/><path clip-rule="evenodd" class="m94p08b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:user-clock-solid" {...props}></Icon>
