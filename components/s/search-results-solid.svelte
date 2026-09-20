<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq9z85bal.css';
import '../../css/x/xlo2ptjbm.css';
import '../../css/k/kemfy5bie.css';
import '../../css/e/eu-9hmdib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq9z85bal"/><path class="xlo2ptjbm"/><path clip-rule="evenodd" class="kemfy5bie"/><path class="eu-9hmdib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-results-solid" {...props}></Icon>
